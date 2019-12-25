# sringgt
useless
无用的
package com.cskaoyan.ssm.bean;

import lombok.Data;

@Data
public class User {

    String name;

    Integer cash;

    public String getName() {
        return name;
    }

    public User setName(String name) {
        this.name = name;
        return this;
    }

    public Integer getCash() {
        return cash;
    }

    public User setCash(Integer cash) {
        this.cash = cash;
        return this;
    }
}

