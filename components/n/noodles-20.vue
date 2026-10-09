<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa0mk_bnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fa0mk_bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:noodles-20" /></template>
