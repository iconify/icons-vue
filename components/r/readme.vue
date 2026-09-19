<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az-hr7b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="az-hr7b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:readme" /></template>
