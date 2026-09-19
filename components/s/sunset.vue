<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/r/r6jxgebue.css';
import '../../css/a/a7oce5bvd.css';
import '../../css/h/hnnvz45cz.css';
import '../../css/s/segv2ibyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="r6jxgebue"/><path class="a7oce5bvd"/><path class="hnnvz45cz"/><circle class="segv2ibyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:sunset" /></template>
