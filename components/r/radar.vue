<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljrl82byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljrl82byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:radar" /></template>
