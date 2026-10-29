<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/ts5wvh0-e.css';
import '../../css/g/g7tyw9b-d.css';
import '../../css/r/rga4tyjvs.css';
import '../../css/s/s8b50cb0q.css';
import '../../css/v/v-s5uj85x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ts5wvh0-e wm-k"/><path class="g7tyw9b-d wm-k"/><path class="rga4tyjvs wm-k"/><path class="s8b50cb0q wm-shine"/><path class="v-s5uj85x wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:message-square-text" /></template>
