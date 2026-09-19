<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0x_k8bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k0x_k8bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rusty-sword" /></template>
