<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yywrzcbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yywrzcbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:military-police-officer" /></template>
