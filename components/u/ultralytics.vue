<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3jn_hbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="o3jn_hbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:ultralytics" /></template>
