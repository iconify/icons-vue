<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg_orq4_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bg_orq4_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stahlhelm" /></template>
