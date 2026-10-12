<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-7bc4bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-7bc4bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:stroke-style-line" /></template>
