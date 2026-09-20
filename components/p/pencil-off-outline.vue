<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldat04b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldat04b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pencil-off-outline" /></template>
