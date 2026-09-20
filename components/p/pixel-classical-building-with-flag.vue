<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c17dyebzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c17dyebzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-classical-building-with-flag" /></template>
