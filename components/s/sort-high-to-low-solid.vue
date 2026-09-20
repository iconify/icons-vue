<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh-4jo2tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="gh-4jo2tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sort-high-to-low-solid" /></template>
