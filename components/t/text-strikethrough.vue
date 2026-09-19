<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atkvy_bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="atkvy_bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-strikethrough" /></template>
