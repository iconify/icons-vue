<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc4436bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hc4436bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:next" /></template>
