<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa276fm6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pa276fm6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:view-list" /></template>
