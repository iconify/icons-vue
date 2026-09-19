<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge0s0ukhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ge0s0ukhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:upload" /></template>
