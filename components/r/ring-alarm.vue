<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asi6pxbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asi6pxbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ring-alarm" /></template>
