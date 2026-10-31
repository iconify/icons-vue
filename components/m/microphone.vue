<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/bk0mirbro.css';
import '../../css/g/g6_vs9ynd.css';
import '../../css/o/opmvrxb9o.css';
import '../../css/d/dnvwyvf3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="bk0mirbro wm-shadow"/><path class="g6_vs9ynd wm-shadow"/><path class="opmvrxb9o"/><path class="dnvwyvf3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:microphone" /></template>
