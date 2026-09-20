<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww04fyd9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww04fyd9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rename-box-outline" /></template>
