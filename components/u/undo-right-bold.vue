<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caoutqb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="caoutqb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-right-bold" /></template>
