<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd4gkhtwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pd4gkhtwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:witch-face" /></template>
