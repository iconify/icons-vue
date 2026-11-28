<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1w820bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1w820bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:workflow-play" /></template>
