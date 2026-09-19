<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3_a3ew6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3_a3ew6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:monday" /></template>
