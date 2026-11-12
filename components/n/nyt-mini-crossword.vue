<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcsewxa-q.css';
import '../../css/t/t6ojfgbzo.css';
import '../../css/z/zj67j_bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zcsewxa-q"/><path class="t6ojfgbzo"/><path class="zj67j_bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-mini-crossword" /></template>
