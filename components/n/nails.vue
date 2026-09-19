<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8wuwhb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o8wuwhb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:nails" /></template>
