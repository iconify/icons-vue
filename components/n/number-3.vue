<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5nykxe0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5nykxe0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:number-3" /></template>
