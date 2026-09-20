<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy6_ilbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xy6_ilbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mean" /></template>
