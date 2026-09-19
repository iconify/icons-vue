<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfomj3bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xfomj3bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:webcomponents-org" /></template>
