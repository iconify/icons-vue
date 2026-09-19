<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaeie20lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eaeie20lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:shovel" /></template>
