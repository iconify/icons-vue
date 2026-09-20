<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2ktfdbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y2ktfdbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-remove-subtract-solid" /></template>
