<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj988qb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="sj988qb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:vuejs" /></template>
