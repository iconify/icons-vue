<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r67p6-b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r67p6-b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-underline" /></template>
