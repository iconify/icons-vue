<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3eseacbm.css';
import '../../css/n/nc_t_0bbz.css';
import '../../css/a/avq41vbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="d3eseacbm"/><path class="nc_t_0bbz"/><path class="avq41vbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pocketbase" /></template>
