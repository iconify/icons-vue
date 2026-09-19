<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plj97-bxh.css';
import '../../css/m/moc8vccjz.css';
import '../../css/p/p_4oxsb6e.css';
import '../../css/o/o-8l1okzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plj97-bxh"/><circle class="moc8vccjz"/><circle class="p_4oxsb6e"/><path class="o-8l1okzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:router" /></template>
