<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1jtovu1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m1jtovu1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:saved" /></template>
