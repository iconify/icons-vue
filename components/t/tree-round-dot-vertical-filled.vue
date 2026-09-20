<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de09431ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de09431ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tree-round-dot-vertical-filled" /></template>
