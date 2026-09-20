<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5r2seb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c5r2seb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:wheelbarrow-empty" /></template>
