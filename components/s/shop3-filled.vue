<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aov95pblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aov95pblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shop3-filled" /></template>
