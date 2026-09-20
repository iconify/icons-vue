<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiw7po6xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oiw7po6xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:telebugs-dark" /></template>
