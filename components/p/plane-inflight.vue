<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgu5rybei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgu5rybei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plane-inflight" /></template>
