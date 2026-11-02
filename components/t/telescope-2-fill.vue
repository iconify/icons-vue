<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex_0f5bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex_0f5bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:telescope-2-fill" /></template>
