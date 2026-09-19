<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/f/f_i-55w-x.css';
import '../../css/k/kl6xp4spr.css';
import '../../css/a/a31hkfdiu.css';
import '../../css/i/iahmlcbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="f_i-55w-x"/><path class="kl6xp4spr"/><circle class="a31hkfdiu"/><circle class="iahmlcbgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:owl" /></template>
