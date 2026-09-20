<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj7pex86r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hj7pex86r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:pet-animals-pig" /></template>
