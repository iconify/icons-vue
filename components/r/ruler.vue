<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i133w3y_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i133w3y_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ruler" /></template>
