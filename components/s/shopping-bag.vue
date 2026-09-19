<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzdbhquoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xzdbhquoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:shopping-bag" /></template>
