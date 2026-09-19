<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-8m2-e6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k-8m2-e6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:phone" /></template>
