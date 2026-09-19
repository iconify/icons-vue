<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u15iko0yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u15iko0yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:windows" /></template>
