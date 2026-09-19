<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4zr8ab3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a4zr8ab3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sandal" /></template>
