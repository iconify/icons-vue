<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7h3y_73d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n7h3y_73d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vomiting" /></template>
