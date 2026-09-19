<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg0ptgbvl.css';
import '../../css/y/y6o2cyb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eg0ptgbvl"/><path class="y6o2cyb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:notebook" /></template>
