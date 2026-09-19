<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yosik5bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yosik5bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:person-x-fill" /></template>
