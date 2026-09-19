<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naovz_vyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="naovz_vyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sword-brandish" /></template>
