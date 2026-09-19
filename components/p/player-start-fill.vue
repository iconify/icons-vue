<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxrdkngpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oxrdkngpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-start-fill" /></template>
