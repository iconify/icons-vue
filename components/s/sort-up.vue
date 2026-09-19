<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0dhnlbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="n0dhnlbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sort-up" /></template>
