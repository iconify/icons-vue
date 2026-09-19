<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxnxqlq1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pxnxqlq1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:rollup-js" /></template>
