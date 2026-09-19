<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/e/eldoky0en.css';
import '../../css/a/ajxep-bpy.css';
import '../../css/n/nxcjdzsby.css';
import '../../css/o/oa0qdzgod.css';
import '../../css/j/jyjk2cs2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="eldoky0en"/><path class="ajxep-bpy"/><circle class="nxcjdzsby"/><circle class="oa0qdzgod"/><path class="jyjk2cs2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:videocamera-one" /></template>
