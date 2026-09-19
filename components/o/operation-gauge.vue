<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7_ef0bll.css';
import '../../css/w/ww0v738xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b7_ef0bll"/><path class="ww0v738xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:operation-gauge" /></template>
