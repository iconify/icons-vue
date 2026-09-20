<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdh1b5bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cdh1b5bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-square-bold" /></template>
