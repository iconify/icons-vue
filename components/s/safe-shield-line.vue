<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w90ht-b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w90ht-b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-shield-line" /></template>
