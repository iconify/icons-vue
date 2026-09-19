<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiqbcvbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uiqbcvbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:reorder-four" /></template>
