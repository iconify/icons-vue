<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff0tn4i0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ff0tn4i0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:whirlwind" /></template>
