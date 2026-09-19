<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf-g88cab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="tf-g88cab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:y" /></template>
