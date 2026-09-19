<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buk6hlfsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="buk6hlfsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:t-shirt" /></template>
