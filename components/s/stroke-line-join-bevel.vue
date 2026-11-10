<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv898niqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv898niqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:stroke-line-join-bevel" /></template>
