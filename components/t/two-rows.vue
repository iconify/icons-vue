<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpurzkbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpurzkbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:two-rows" /></template>
