<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwlopty2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jwlopty2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:slider-horizontal-3" /></template>
