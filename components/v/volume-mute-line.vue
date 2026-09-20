<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u30jk17_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u30jk17_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:volume-mute-line" /></template>
