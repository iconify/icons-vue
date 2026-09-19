<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wub5tac1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wub5tac1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:source-control" /></template>
