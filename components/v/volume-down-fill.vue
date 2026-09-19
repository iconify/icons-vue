<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/necg2lb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="necg2lb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:volume-down-fill" /></template>
