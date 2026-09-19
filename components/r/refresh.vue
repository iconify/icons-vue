<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlhgx7bdi.css';
import '../../css/n/nx3hbtbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="zlhgx7bdi"/><path class="nx3hbtbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:refresh" /></template>
