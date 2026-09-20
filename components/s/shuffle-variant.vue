<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chm_rl1fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chm_rl1fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shuffle-variant" /></template>
