<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taydys9dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taydys9dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rune" /></template>
