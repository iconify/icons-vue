<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hax0k24xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hax0k24xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:screen-1-solid" /></template>
