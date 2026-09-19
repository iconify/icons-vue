<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oakaq48zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oakaq48zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-5-circle-fill" /></template>
