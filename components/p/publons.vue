<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljc5zc_ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="ljc5zc_ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:publons" /></template>
