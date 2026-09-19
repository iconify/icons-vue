<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-7v9o66a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m-7v9o66a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:person" /></template>
