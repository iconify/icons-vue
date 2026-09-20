<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc8vzvbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wc8vzvbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:virus-antivirus-remix" /></template>
