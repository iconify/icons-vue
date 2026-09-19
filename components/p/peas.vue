<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zer6dxb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zer6dxb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:peas" /></template>
