<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6grok_ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n6grok_ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:recycle-bin-3-solid" /></template>
