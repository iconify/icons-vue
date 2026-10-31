<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/bga_7bc3z.css';
import '../../css/h/hjy563b8z.css';
import '../../css/h/hyb74pb9k.css';
import '../../css/i/ip9g62bcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="bga_7bc3z wm-shadow"/><path class="hjy563b8z wm-shadow"/><path class="hyb74pb9k"/><path class="ip9g62bcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:sd-card" /></template>
