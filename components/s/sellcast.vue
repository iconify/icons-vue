<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f14uakred.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="f14uakred"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:sellcast" /></template>
