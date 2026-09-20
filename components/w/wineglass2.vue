<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwgy-bblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qwgy-bblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wineglass2" /></template>
