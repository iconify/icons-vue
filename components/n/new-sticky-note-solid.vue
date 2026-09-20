<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9ushmagt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e9ushmagt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:new-sticky-note-solid" /></template>
