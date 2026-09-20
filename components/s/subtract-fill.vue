<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi3x8dbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fi3x8dbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:subtract-fill" /></template>
