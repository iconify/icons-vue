<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beprfqbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="beprfqbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:music-disk-cd-1" /></template>
