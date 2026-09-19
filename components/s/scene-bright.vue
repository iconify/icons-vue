<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh0ww_rwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh0ww_rwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:scene-bright" /></template>
