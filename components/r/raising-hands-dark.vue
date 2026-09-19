<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ilwj9wk9f.css';
import '../../css/g/gzzb74pus.css';
import '../../css/d/de29zjbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ilwj9wk9f"/><path class="gzzb74pus"/><path class="de29zjbhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:raising-hands-dark" /></template>
