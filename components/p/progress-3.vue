<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsq7xeoxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="xsq7xeoxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:progress-3" /></template>
