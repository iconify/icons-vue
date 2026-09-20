<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3_xu5-hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3_xu5-hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:merge-type" /></template>
