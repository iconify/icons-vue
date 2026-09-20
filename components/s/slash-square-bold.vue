<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obu2jwbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="obu2jwbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slash-square-bold" /></template>
