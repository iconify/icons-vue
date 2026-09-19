<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k672c4brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k672c4brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:pinterest" /></template>
