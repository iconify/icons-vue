<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyvic_bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gyvic_bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tired-face-with-z-in-circle" /></template>
