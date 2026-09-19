<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7mt7bzuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="t7mt7bzuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:temperature-arrow-up" /></template>
