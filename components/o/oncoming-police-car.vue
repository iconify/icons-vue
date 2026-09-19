<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0hssn4us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k0hssn4us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:oncoming-police-car" /></template>
