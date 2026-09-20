<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwg8mfbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwg8mfbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:moon-filled" /></template>
