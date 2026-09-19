<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lef9jzxzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lef9jzxzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:no-ticket" /></template>
