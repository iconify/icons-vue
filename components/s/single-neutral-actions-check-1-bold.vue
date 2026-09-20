<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc0uu2uxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc0uu2uxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:single-neutral-actions-check-1-bold" /></template>
