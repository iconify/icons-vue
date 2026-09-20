<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epst0e1jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epst0e1jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-5-box-multiple" /></template>
