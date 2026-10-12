<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6cssibrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6cssibrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-line-style" /></template>
