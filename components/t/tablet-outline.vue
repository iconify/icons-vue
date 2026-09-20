<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk6jsc0yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hk6jsc0yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:tablet-outline" /></template>
