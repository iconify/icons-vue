<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgarisb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lgarisb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sort-down" /></template>
