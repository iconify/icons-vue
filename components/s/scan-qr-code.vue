<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m45m7yblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m45m7yblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:scan-qr-code" /></template>
