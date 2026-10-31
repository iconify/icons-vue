<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/i/i5-20q0_t.css';
import '../../css/r/rdktr3xsg.css';
import '../../css/f/f61_c6nui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="i5-20q0_t wm-shadow"/><path class="rdktr3xsg wm-shadow"/><path class="f61_c6nui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:spider-web" /></template>
