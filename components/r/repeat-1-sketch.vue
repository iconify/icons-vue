<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f33kfsb_i.css';
import '../../css/t/t7u-f0bvj.css';
import '../../css/s/skebkz5in.css';
import '../../css/l/lgxikgbwv.css';
import '../../css/g/g8ed_dbcn.css';
import '../../css/e/e1fzs96go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f33kfsb_i wm-k"/><path class="t7u-f0bvj wm-a"/><path class="skebkz5in wm-s"/><path class="lgxikgbwv wm-k"/><path class="g8ed_dbcn wm-a"/><path class="e1fzs96go wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:repeat-1-sketch" /></template>
