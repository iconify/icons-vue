<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-2wlkbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u-2wlkbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:right-small-fill" /></template>
