<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxe30nuth.css';
import '../../css/i/i5z920-bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxe30nuth"/><path class="i5z920-bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:screencast-2-bold" /></template>
