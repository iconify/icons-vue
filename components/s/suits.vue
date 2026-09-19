<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhwt459hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zhwt459hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:suits" /></template>
