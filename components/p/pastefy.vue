<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8z18xbtt.css';
import '../../css/j/j1680wbis.css';
import '../../css/a/aavykeq3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n8z18xbtt"/><path class="j1680wbis"/><path class="aavykeq3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pastefy" /></template>
