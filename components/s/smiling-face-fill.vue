<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v27n-xo4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v27n-xo4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:smiling-face-fill" /></template>
