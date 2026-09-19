<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv2n_6bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nv2n_6bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:search" /></template>
