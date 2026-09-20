<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfx0fabyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfx0fabyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:star-rainbow-filled" /></template>
