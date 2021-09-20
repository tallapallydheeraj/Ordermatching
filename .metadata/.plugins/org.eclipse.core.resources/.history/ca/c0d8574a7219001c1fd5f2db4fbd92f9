package com.dbs.ordermatching.repo;

import java.util.List;

import org.springframework.data.jpa.repository.JpaRepository;
import org.springframework.data.repository.CrudRepository;
import org.springframework.stereotype.Repository;

import com.dbs.ordermatching.model.Client;
import com.dbs.ordermatching.model.Custodian;
@Repository
public interface ClientRepository extends JpaRepository<Client, String> {
	
	public List<Client> findByCustodian(Custodian custodian);
}
