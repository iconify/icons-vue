<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/vfl_-cgfn.css';
import '../../css/b/btnov_7jm.css';
import '../../css/x/xcwbr8b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vfl_-cgfn"/><path class="btnov_7jm"/><path class="xcwbr8b4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:note-favorite" /></template>
