<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiwn76bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiwn76bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:minimize-solid" /></template>
