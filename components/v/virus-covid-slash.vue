<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uooe_ab7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="uooe_ab7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:virus-covid-slash" /></template>
