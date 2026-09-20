<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuj-c2blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kuj-c2blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pikvm-light" /></template>
