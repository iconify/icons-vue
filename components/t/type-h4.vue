<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px7wvdboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="px7wvdboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:type-h4" /></template>
