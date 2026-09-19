<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8d7wgb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q8d7wgb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:view-split" /></template>
