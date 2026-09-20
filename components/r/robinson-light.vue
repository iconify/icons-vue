<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tecp77bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tecp77bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:robinson-light" /></template>
