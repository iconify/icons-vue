<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psl9fr_lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="psl9fr_lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sonic-boom" /></template>
