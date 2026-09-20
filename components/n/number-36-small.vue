<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh4zsyiic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh4zsyiic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-36-small" /></template>
