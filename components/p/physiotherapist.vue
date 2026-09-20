<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiwq88sdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="yiwq88sdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:physiotherapist" /></template>
