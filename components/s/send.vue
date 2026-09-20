<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-t7k5nxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-t7k5nxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:send" /></template>
