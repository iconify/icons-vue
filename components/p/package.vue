<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-dfo1ysz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="g-dfo1ysz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:package" /></template>
