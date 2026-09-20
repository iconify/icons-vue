<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eae-4-bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eae-4-bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:note-multiple" /></template>
