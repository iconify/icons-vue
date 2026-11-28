<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3mp-kbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o3mp-kbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:soft-serve-in-cup" /></template>
