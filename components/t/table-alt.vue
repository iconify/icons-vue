<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/civ9npw1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1472};
const content = `<path class="civ9npw1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:table-alt" /></template>
