<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v57k_lqgn.css';
import '../../css/c/cql0n4wpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v57k_lqgn"/><path class="cql0n4wpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:towels-20-bold" /></template>
