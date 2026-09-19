<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa6_aehaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="pa6_aehaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:umbrella-beach" /></template>
