<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y2ss9hb6d.css';
import '../../css/s/sf0wjubya.css';
import '../../css/s/s4gz9abla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="y2ss9hb6d"/><path class="sf0wjubya"/><path class="s4gz9abla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:shield" /></template>
