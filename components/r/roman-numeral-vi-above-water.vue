<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p05ebdbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p05ebdbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-vi-above-water" /></template>
