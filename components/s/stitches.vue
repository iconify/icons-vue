<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8naembgy.css';
import '../../css/f/fow0mdbxw.css';
import '../../css/x/xaxzevb3j.css';
import '../../css/p/pz4dgsbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g clip-rule="evenodd" class="u8naembgy"><path class="fow0mdbxw"/><path class="xaxzevb3j"/><path class="pz4dgsbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:stitches" /></template>
