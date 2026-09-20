<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-s8rx_ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-s8rx_ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:subtitles" /></template>
