<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-sj2ebsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k-sj2ebsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-in-fill-16" /></template>
