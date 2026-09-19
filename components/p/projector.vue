<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kyqu4bcuc.css';
import '../../css/p/p4twwqb1d.css';
import '../../css/p/pu-813bvk.css';
import '../../css/h/hgi_w8bde.css';
import '../../css/n/nbnss9m8h.css';
import '../../css/l/l7kugy4ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="kyqu4bcuc"/><path class="p4twwqb1d"/><path class="pu-813bvk"/><path class="hgi_w8bde"/><circle class="nbnss9m8h"/><circle class="l7kugy4ne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:projector" /></template>
