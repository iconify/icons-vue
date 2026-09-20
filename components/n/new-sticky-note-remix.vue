<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl_um2bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sl_um2bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:new-sticky-note-remix" /></template>
