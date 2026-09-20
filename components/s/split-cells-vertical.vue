<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg3ymujxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg3ymujxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:split-cells-vertical" /></template>
