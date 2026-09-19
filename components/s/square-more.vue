<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjug9ybmp.css';
import '../../css/e/ecuj1-btq.css';
import '../../css/h/hk8vu0bed.css';
import '../../css/u/ur4hs2dgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjug9ybmp"/><circle class="ecuj1-btq"/><circle class="hk8vu0bed"/><circle class="ur4hs2dgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:square-more" /></template>
