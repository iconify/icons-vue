<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9mz1tb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c9mz1tb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:t-mobile-light" /></template>
