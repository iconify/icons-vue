<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftahcfb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="ftahcfb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pawn" /></template>
