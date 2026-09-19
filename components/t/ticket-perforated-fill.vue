<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dybwt5b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dybwt5b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:ticket-perforated-fill" /></template>
