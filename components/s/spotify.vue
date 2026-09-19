<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w95g0dfgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":488};
const content = `<path class="w95g0dfgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:spotify" /></template>
