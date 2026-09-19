<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u31l4ebpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="u31l4ebpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:submit" /></template>
