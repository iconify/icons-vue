<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhtb0jn5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhtb0jn5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:warning-hexagon" /></template>
