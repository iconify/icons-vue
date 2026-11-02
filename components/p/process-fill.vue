<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oubgc4blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oubgc4blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:process-fill" /></template>
