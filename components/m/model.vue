<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thw6rvjmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="thw6rvjmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:model" /></template>
