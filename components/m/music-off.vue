<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzpvso9zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzpvso9zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:music-off" /></template>
