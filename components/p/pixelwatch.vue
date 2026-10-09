<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcy7zcc9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcy7zcc9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pixelwatch" /></template>
