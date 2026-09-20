<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muj7qwivj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muj7qwivj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:video-fill" /></template>
