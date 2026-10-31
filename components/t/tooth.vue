<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/p/pxct46bku.css';
import '../../css/k/k47f7hbpk.css';
import '../../css/b/bx17z-g6f.css';
import '../../css/h/h44u2vsze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="pxct46bku wm-shadow"/><path class="k47f7hbpk wm-shadow"/><path class="bx17z-g6f"/><path class="h44u2vsze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:tooth" /></template>
