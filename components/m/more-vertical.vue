<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/v/vi1qgybkc.css';
import '../../css/l/lk0ygb_nh.css';
import '../../css/r/rh9qoibkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="vi1qgybkc"/><path class="lk0ygb_nh"/><path class="rh9qoibkn wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:more-vertical" /></template>
