<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvrr3kbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvrr3kbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zoom-in-area" /></template>
