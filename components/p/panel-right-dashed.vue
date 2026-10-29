<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv78cwbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv78cwbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:panel-right-dashed" /></template>
