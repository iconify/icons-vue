<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jljdwobfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jljdwobfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:square-brackets-circle-remix" /></template>
