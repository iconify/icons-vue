<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dzwjvva5h.css';
import '../../css/d/dianddcsu.css';
import '../../css/o/ovtl0ejmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="dzwjvva5h"/><path class="dianddcsu"/><path class="ovtl0ejmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:scientist" /></template>
