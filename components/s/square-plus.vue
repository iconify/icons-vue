<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6h98eu1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6h98eu1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-plus" /></template>
