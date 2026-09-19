<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b56svt4rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b56svt4rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ninja-mask" /></template>
