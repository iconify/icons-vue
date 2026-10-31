<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p387bwbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p387bwbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-padding-horizontal-filled" /></template>
