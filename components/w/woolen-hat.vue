<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/uc-_c65-l.css';
import '../../css/r/r55hgqb1c.css';
import '../../css/g/gnkx5hbtb.css';
import '../../css/p/peqvy84ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="uc-_c65-l"/><path class="r55hgqb1c"/><circle class="gnkx5hbtb"/><path class="peqvy84ye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:woolen-hat" /></template>
