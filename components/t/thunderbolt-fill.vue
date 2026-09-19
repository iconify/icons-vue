<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu8nhg2df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pu8nhg2df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:thunderbolt-fill" /></template>
