<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr9w9cuwd.css';
import '../../css/u/umljw05vc.css';
import '../../css/k/k0zklwbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr9w9cuwd"/><path class="umljw05vc"/><path class="k0zklwbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:vault" /></template>
