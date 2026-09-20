<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k56efgb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k56efgb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mazanoke-light" /></template>
