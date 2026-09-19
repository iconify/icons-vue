<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0g1ggb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0g1ggb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:your-spotify" /></template>
