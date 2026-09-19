<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-2-4obch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-2-4obch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:roomscomputer" /></template>
