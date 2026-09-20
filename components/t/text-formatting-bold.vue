<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trywkjrja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="trywkjrja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:text-formatting-bold" /></template>
