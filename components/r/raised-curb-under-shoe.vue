<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5_k12b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i5_k12b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:raised-curb-under-shoe" /></template>
