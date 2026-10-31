<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/v/vu5hsac0o.css';
import '../../css/m/mxqq5lbuu.css';
import '../../css/o/o0ihot2mh.css';
import '../../css/j/j75bsibgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="vu5hsac0o wm-shadow"/><path class="mxqq5lbuu wm-shadow"/><path class="o0ihot2mh"/><path class="j75bsibgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:scan" /></template>
