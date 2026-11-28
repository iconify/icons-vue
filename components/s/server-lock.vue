<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rav0esbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rav0esbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:server-lock" /></template>
