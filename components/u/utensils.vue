<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7n261t5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7n261t5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:utensils" /></template>
