<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9wx0431p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9wx0431p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paperclip-duo" /></template>
