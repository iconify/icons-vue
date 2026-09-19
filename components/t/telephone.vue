<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx8s6199m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kx8s6199m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:telephone" /></template>
