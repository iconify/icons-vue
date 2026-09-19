<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojgk9hbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojgk9hbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:splash" /></template>
