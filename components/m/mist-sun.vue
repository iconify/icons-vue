<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cauac2ggz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cauac2ggz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:mist-sun" /></template>
