<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmv0kzbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmv0kzbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:slack-solid" /></template>
