<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai8kln8xl.css';
import '../../css/e/er6idhbcf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ai8kln8xl clr-i-outline clr-i-outline-path-1"/><path class="clr-i-outline clr-i-outline-path-2 er6idhbcf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:unlink-line" /></template>
