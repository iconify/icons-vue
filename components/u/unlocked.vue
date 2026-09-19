<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l4t7nkb3h.css';
import '../../css/x/xuyrlebfz.css';
import '../../css/u/ugsg8xbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="l4t7nkb3h"/><path class="xuyrlebfz"/><path class="ugsg8xbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:unlocked" /></template>
