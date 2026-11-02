<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcw1hs52e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcw1hs52e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-4-line" /></template>
