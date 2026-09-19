<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c18zojbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c18zojbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mushrooms-cluster" /></template>
