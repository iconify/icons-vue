<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/p/pbruvwbic.css';
import '../../css/b/b064tu1ws.css';
import '../../css/q/qjfhldb9u.css';
import '../../css/s/sc_fqnbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="pbruvwbic"/><path class="b064tu1ws"/><circle class="qjfhldb9u"/><path class="sc_fqnbin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:pic-one" /></template>
