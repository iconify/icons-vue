<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg-cnbbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wg-cnbbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:polygonal-lasso-tool-solid" /></template>
