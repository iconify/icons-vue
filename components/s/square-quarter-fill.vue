<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5gpqjb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f5gpqjb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-quarter-fill" /></template>
