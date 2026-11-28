<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i748oxbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i748oxbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pull-request-clock" /></template>
