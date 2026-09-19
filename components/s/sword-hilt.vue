<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iamj04z-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iamj04z-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sword-hilt" /></template>
