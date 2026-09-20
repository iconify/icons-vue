<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9l6ipbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o9l6ipbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:tesla" /></template>
