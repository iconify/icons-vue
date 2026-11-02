<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eszcsz2gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eszcsz2gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moonlight-line" /></template>
