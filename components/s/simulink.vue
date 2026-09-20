<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz-uhfsal.css';
import '../../css/h/hn2o_abjx.css';
import '../../css/w/wdbpibcck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":4.233,"height":4.233};
const content = `<path class="pz-uhfsal"/><path class="hn2o_abjx"/><path class="wdbpibcck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:simulink" /></template>
