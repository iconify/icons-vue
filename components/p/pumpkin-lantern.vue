<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8s-p2b0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b8s-p2b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pumpkin-lantern" /></template>
