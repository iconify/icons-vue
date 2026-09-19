<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu19bjyrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hu19bjyrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tron-arrow" /></template>
