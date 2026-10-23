<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc3rm7mko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc3rm7mko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:navigation" /></template>
