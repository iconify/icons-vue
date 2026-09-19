<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anw272b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="anw272b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:viewfinder-circle-16-solid" /></template>
