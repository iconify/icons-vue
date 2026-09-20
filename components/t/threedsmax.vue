<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/speqq-bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="speqq-bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:threedsmax" /></template>
