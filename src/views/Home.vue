<template>
<div>
    <div>Home view</div>
    <div><Nav /></div>
    <div><MainHeader /></div>
    <div><Presentation :oriented="left"/></div>
    <div><Presentation :oriented="right"/></div>
    <div><Stats /></div>
    <div><Tabs /></div>
    <div><Footer /></div>
</div>
</template>
<script setup>
import { Nav, MainHeader, Presentation, Stats, Tabs, Footer } from '../components'
</script>