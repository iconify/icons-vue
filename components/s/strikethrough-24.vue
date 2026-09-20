<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtvgt3blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtvgt3blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:strikethrough-24" /></template>
