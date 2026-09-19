<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgntcj60t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hgntcj60t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sunrise-fill" /></template>
