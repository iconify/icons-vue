<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7yn-bb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="r7yn-bb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-stop-bold" /></template>
