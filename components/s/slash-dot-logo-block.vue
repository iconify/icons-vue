<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmf-2wqcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tmf-2wqcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:slash-dot-logo-block" /></template>
