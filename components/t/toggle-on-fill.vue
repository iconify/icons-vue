<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5_cm4b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5_cm4b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:toggle-on-fill" /></template>
