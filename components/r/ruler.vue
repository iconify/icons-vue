<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yse31pbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yse31pbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ruler" /></template>
