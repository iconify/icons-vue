<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-hns2b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g-hns2b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:split-arrows" /></template>
