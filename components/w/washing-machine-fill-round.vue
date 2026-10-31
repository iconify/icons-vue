<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqd9lfbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqd9lfbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:washing-machine-fill-round" /></template>
