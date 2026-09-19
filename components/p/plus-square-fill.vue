<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-nfe_bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l-nfe_bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:plus-square-fill" /></template>
