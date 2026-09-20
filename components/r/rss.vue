<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qes_-u4hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qes_-u4hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:rss" /></template>
