<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnbpl8blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnbpl8blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pencil-pause" /></template>
