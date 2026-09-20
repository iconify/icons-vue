<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6s-y4r-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y6s-y4r-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:step-1" /></template>
