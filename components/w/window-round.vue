<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm_y01bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm_y01bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-round" /></template>
