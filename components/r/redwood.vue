<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfo87_b9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cfo87_b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:redwood" /></template>
