<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q30oaffoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q30oaffoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:sort-line" /></template>
