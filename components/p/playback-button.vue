<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb01yyb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb01yyb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:playback-button" /></template>
