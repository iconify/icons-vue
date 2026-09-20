<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws_650b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ws_650b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-anticlockwise-1-fill" /></template>
