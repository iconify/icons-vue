<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n34rgbcue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n34rgbcue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rewind-solid" /></template>
