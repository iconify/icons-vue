<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4y1onb8u.css';
import '../../css/y/ybqrj5brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o4y1onb8u"/><path class="ybqrj5brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:package-check-filled" /></template>
