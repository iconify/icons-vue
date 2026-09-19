<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuge6-bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":405,"height":512};
const content = `<path class="kuge6-bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:stencil" /></template>
