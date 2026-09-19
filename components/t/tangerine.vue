<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdvp3-bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fdvp3-bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tangerine" /></template>
