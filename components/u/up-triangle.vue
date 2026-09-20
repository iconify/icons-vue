<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhw8w_bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uhw8w_bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:up-triangle" /></template>
