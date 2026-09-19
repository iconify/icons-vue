<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeyf-3b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeyf-3b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:screen-full-duotone" /></template>
