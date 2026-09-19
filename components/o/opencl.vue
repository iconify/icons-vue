<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdf5exf4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tdf5exf4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:opencl" /></template>
