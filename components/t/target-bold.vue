<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/pvkpvmyui.css';
import '../../css/v/vvjm9e27u.css';
import '../../css/q/q56rgfbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="pvkpvmyui"/><path class="vvjm9e27u"/><path class="q56rgfbjg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:target-bold" /></template>
