<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/symc4kb7p.css';
import '../../css/n/n7ijnpbfo.css';
import '../../css/f/fna-v2b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="symc4kb7p"/><path class="n7ijnpbfo"/><path class="fna-v2b9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:top-hat" /></template>
