<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b0i93bfvu.css';
import '../../css/k/k33gfyfri.css';
import '../../css/w/wwr-czu3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="b0i93bfvu"/><path class="k33gfyfri"/><path class="wwr-czu3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:pinched-fingers-dark" /></template>
