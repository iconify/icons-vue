<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x__7wzbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x__7wzbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-ii-over-water" /></template>
