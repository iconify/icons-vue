<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttzw69b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttzw69b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spiral" /></template>
