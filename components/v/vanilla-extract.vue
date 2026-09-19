<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoeyw0blc.css';
import '../../css/h/hg2rozmww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eoeyw0blc"/><path class="hg2rozmww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:vanilla-extract" /></template>
