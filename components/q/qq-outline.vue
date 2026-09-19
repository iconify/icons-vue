<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyiadsbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cyiadsbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:qq-outline" /></template>
