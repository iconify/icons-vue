<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9zw1s-vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9zw1s-vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:subscript" /></template>
