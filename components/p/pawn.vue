<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jumt7_b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":242,"height":512};
const content = `<path class="jumt7_b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pawn" /></template>
