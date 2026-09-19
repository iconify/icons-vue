<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mq5hsbogj.css';
import '../../css/r/r6awccc6t.css';
import '../../css/u/uabr8jwvk.css';
import '../../css/a/ab8uwfbkd.css';
import '../../css/b/ba32q9bun.css';
import '../../css/c/cvu_axbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="mq5hsbogj"/><path class="r6awccc6t"/><path class="uabr8jwvk"/><path class="ab8uwfbkd"/><path class="ba32q9bun"/><path class="cvu_axbai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:spiral-notepad" /></template>
