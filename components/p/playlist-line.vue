<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh7l6ubcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh7l6ubcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:playlist-line" /></template>
