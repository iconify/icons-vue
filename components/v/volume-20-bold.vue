<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqvgs1b3g.css';
import '../../css/u/uiqysqbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gqvgs1b3g"/><path class="uiqysqbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-20-bold" /></template>
