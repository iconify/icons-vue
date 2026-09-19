<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s7zs4u8eo.css';
import '../../css/b/bbc2fccsv.css';
import '../../css/t/t3du_ox9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="s7zs4u8eo"/><path class="bbc2fccsv"/><path class="t3du_ox9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:wilted-flower" /></template>
