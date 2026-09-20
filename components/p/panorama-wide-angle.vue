<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzehumb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzehumb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:panorama-wide-angle" /></template>
