<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nybr-g8gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nybr-g8gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:more-2-line" /></template>
