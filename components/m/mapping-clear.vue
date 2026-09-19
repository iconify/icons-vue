<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooq9ajsgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ooq9ajsgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mapping-clear" /></template>
