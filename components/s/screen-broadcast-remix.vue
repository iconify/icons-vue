<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stdim8zrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="stdim8zrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:screen-broadcast-remix" /></template>
