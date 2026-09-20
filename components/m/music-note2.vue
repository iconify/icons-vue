<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tidolwinm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tidolwinm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-note2" /></template>
