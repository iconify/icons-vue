<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/why_b6bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="why_b6bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:xxx" /></template>
