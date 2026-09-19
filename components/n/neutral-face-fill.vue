<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffi5e5btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ffi5e5btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:neutral-face-fill" /></template>
