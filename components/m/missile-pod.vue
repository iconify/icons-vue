<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri7kwcc0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ri7kwcc0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:missile-pod" /></template>
