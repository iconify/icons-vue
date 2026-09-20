<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4w5gdb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="o4w5gdb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:stack" /></template>
