<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyjxwfb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cyjxwfb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:star-16" /></template>
