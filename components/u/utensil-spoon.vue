<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl0hn4bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pl0hn4bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:utensil-spoon" /></template>
