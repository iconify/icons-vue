<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al0ofebsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al0ofebsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:square-2-stack" /></template>
