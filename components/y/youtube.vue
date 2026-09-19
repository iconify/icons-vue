<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezo0bkj3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ezo0bkj3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:youtube" /></template>
