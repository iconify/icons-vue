<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v0jfpwl4b.css';
import '../../css/l/lwyv-mb2r.css';
import '../../css/q/qq5frsb4s.css';
import '../../css/y/y5qw9jris.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v0jfpwl4b"/><path class="lwyv-mb2r wm-a"/><path class="qq5frsb4s wm-k"/><path class="wm-a y5qw9jris"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:taxi-sketch" /></template>
