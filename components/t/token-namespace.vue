<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caufp1b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="caufp1b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-namespace" /></template>
