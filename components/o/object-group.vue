<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g65zm-xgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="g65zm-xgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:object-group" /></template>
