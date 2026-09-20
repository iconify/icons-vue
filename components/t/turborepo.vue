<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5-lonbvr.css';
import '../../css/c/cs_yflpck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5-lonbvr"/><path clip-rule="evenodd" class="cs_yflpck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:turborepo" /></template>
