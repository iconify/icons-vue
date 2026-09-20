<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk487_b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":302};
const content = `<path class="pk487_b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:storyblok" /></template>
