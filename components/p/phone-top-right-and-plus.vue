<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1o9wsbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m1o9wsbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-top-right-and-plus" /></template>
