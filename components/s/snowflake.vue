<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy519s08g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy519s08g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:snowflake" /></template>
