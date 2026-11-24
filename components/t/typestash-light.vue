<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5g7mrbhx.css';
import '../../css/h/hnc9r9bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g5g7mrbhx"/><path class="hnc9r9bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typestash-light" /></template>
