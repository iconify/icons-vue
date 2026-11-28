<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr2x3naix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr2x3naix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:merge-solid" /></template>
