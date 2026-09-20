<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4w278ztg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4w278ztg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-right-dashed" /></template>
