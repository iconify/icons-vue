<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/ssxi8fbrc.css';
import '../../css/q/qzi6x3eeu.css';
import '../../css/b/bqwt9iilj.css';
import '../../css/f/ftvkakb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ssxi8fbrc wm-shadow"/><path class="qzi6x3eeu wm-shadow"/><path class="bqwt9iilj"/><path class="ftvkakb5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:target" /></template>
