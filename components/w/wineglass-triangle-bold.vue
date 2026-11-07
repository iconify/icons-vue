<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb-67rblr.css';
import '../../css/e/el5xkem2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb-67rblr"/><path class="el5xkem2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wineglass-triangle-bold" /></template>
