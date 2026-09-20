<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-w8tuyfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u-w8tuyfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pen-nib-filled" /></template>
