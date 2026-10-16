<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-cif4b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g-cif4b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oil-spill-20" /></template>
