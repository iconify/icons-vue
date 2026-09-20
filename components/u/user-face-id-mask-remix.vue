<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xli1voboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xli1voboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:user-face-id-mask-remix" /></template>
