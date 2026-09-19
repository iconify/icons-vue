<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_smyob6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z_smyob6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:stars" /></template>
