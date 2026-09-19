<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt-cjh-ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mt-cjh-ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:right-panel-show" /></template>
