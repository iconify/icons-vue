<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbl9vnbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vbl9vnbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:straight-ruler" /></template>
