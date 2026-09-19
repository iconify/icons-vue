<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd0zuvb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hd0zuvb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vacuum-cleaner" /></template>
