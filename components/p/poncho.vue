<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bisr4s8em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bisr4s8em"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:poncho" /></template>
