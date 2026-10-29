<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t2w0vbc1f.css';
import '../../css/v/v9qwxk7pw.css';
import '../../css/v/vx3y4mp6c.css';
import '../../css/p/py-u8epwi.css';
import '../../css/j/j7m6u-b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t2w0vbc1f"/><path class="v9qwxk7pw wm-k"/><path class="vx3y4mp6c wm-k"/><path class="py-u8epwi wm-a"/><path class="j7m6u-b-q wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:panel-left-close-sketch" /></template>
