<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhh2g9tnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhh2g9tnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:remove-row-line" /></template>
