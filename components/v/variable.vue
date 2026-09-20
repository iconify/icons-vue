<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h38ps2bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h38ps2bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:variable" /></template>
