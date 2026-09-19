<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuab06j5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuab06j5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:xing" /></template>
