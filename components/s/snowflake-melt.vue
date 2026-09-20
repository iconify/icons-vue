<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnq988bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnq988bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:snowflake-melt" /></template>
