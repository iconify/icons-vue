<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsg5p00hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rsg5p00hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rows-2-outline" /></template>
