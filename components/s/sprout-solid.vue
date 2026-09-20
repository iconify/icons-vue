<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg7_4ub4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vg7_4ub4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sprout-solid" /></template>
