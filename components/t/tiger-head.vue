<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzpvp6bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nzpvp6bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tiger-head" /></template>
