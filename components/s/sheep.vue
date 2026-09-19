<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk2-8rbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dk2-8rbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sheep" /></template>
