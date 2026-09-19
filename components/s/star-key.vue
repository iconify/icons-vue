<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh-b1pbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lh-b1pbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:star-key" /></template>
