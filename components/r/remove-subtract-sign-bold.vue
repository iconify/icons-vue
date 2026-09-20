<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9r9llbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x9r9llbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:remove-subtract-sign-bold" /></template>
