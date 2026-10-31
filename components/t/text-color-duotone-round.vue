<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x82r1cpjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x82r1cpjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-color-duotone-round" /></template>
