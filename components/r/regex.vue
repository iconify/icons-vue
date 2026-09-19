<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzlx79zxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kzlx79zxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:regex" /></template>
