<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck9wswbnb.css';
import '../../css/a/aifu62-rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ck9wswbnb"/><path class="aifu62-rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smartphone-20" /></template>
