<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk45djb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk45djb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:snail-solid" /></template>
