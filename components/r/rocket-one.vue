<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/d/dyaf68bbe.css';
import '../../css/z/zk794xbdr.css';
import '../../css/s/suau6bcmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="dyaf68bbe"/><circle class="zk794xbdr"/><path class="suau6bcmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:rocket-one" /></template>
