<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq6ply3up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq6ply3up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-arrow-up-solid" /></template>
