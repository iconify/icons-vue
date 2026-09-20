<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0m05kpwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0m05kpwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:subscript" /></template>
