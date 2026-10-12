<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5-qb4ycp.css';
import '../../css/l/l4r5fel4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r5-qb4ycp"/><path class="l4r5fel4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:webcam-off-filled" /></template>
