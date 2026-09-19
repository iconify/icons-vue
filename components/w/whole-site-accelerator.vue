<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/w/wcgsl9y6o.css';
import '../../css/o/obi01p_4h.css';
import '../../css/t/t818okbbd.css';
import '../../css/m/mkv367bpf.css';
import '../../css/f/f08pkdblx.css';
import '../../css/v/vdhgeqfxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="wcgsl9y6o"/><circle class="obi01p_4h"/><circle class="t818okbbd"/><circle class="mkv367bpf"/><path class="f08pkdblx"/><path class="vdhgeqfxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:whole-site-accelerator" /></template>
