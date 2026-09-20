<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntsc62v-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntsc62v-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:zoom-out-fill" /></template>
