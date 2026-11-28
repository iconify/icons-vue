<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jemga0b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jemga0b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:star-off-solid" /></template>
