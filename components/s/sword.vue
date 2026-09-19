<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m89ht4ona.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m89ht4ona"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:sword" /></template>
