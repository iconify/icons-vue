<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbwtjkb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbwtjkb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:server-cog" /></template>
