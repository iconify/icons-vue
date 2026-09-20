<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iws_6ib4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iws_6ib4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:script-2-remix" /></template>
