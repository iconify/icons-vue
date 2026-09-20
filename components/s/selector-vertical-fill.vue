<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k95358occ.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k95358occ"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:selector-vertical-fill" /></template>
