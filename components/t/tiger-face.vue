<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f1nh49bpk.css';
import '../../css/j/je2b2sbsw.css';
import '../../css/d/d1pxylbgo.css';
import '../../css/a/am4jxackm.css';
import '../../css/g/gtv7mrvpa.css';
import '../../css/i/it6opjqek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="f1nh49bpk"/><path class="je2b2sbsw"/><path class="d1pxylbgo"/><path class="am4jxackm"/><path class="gtv7mrvpa"/><path class="it6opjqek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:tiger-face" /></template>
