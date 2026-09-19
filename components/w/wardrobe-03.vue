<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwnuhdcyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwnuhdcyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wardrobe-03" /></template>
