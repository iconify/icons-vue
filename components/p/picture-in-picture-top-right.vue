<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qovv2hjaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qovv2hjaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:picture-in-picture-top-right" /></template>
