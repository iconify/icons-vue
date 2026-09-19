<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l0fzwvb4b.css';
import '../../css/l/l4n1o8blm.css';
import '../../css/s/suffk5-7v.css';
import '../../css/x/xg922ebyc.css';
import '../../css/s/s_p243b7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="l0fzwvb4b"/><path class="l4n1o8blm"/><path class="suffk5-7v"/><path class="xg922ebyc"/><path class="s_p243b7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:movie-camera" /></template>
