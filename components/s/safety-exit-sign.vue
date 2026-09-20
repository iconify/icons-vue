<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwf7vacrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xwf7vacrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:safety-exit-sign" /></template>
