<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_uf02nri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k_uf02nri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:trash-fill" /></template>
