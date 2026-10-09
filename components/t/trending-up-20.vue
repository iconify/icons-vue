<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czalfpt_j.css';
import '../../css/g/g1zbydbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="czalfpt_j"/><path class="g1zbydbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trending-up-20" /></template>
