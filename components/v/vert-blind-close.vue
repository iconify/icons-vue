<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9orw8bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9orw8bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vert-blind-close" /></template>
