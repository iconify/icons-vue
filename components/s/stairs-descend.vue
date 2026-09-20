<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3tf0vicg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n3tf0vicg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:stairs-descend" /></template>
