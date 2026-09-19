<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k33nyj33x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k33nyj33x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:slash" /></template>
