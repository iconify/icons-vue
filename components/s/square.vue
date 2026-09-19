<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9ptvdcsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="w9ptvdcsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:square" /></template>
