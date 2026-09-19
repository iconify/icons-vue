<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khfjhpbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="khfjhpbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sunken-eye" /></template>
