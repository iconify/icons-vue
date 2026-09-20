<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kef3gpz4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kef3gpz4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:traffic-table" /></template>
