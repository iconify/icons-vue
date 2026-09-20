<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7740dnjq.css';
import '../../css/j/jclmsksby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7740dnjq"/><path class="jclmsksby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shuffle-line" /></template>
