<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfphd9she.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cfphd9she"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pearl-earring" /></template>
