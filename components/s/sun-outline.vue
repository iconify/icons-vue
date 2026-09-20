<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0v10zhqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x0v10zhqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sun-outline" /></template>
