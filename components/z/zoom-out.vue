<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n60fh_bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n60fh_bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:zoom-out" /></template>
