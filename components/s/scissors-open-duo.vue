<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cw8bifcxs.css';
import '../../css/s/s63-y8bkd.css';
import '../../css/a/ajrmm7buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="cw8bifcxs"/><path clip-rule="evenodd" class="s63-y8bkd"/><path class="ajrmm7buk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:scissors-open-duo" /></template>
