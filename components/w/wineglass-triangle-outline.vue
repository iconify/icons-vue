<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/craa3rrjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="craa3rrjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wineglass-triangle-outline" /></template>
