<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycp1-7btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycp1-7btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:washing-machine-round" /></template>
