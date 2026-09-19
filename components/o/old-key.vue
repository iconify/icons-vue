<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t1d70xb4w.css';
import '../../css/m/mk1c8-btd.css';
import '../../css/r/rn-2ifxvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="t1d70xb4w"/><path class="mk1c8-btd"/><path class="rn-2ifxvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:old-key" /></template>
