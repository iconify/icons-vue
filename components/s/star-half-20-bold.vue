<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5tis5bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r5tis5bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:star-half-20-bold" /></template>
