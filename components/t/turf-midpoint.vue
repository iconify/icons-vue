<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-el4czwj.css';
import '../../css/b/bp4q0jolu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="u-el4czwj"/><path class="bp4q0jolu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-midpoint" /></template>
