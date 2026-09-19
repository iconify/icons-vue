<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoyfc1bhb.css';
import '../../css/l/lqbe3zbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yoyfc1bhb"/><path class="lqbe3zbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tag" /></template>
