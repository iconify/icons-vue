<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhp66mbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhp66mbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sorting-left-fill" /></template>
