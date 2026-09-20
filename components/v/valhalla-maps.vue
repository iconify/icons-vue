<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnsy8cctb.css';
import '../../css/a/amaky3v5u.css';
import '../../css/m/mtzy7oq7x.css';
import '../../css/s/sa18abbmq.css';
import '../../css/r/r_4ceuibd.css';
import '../../css/s/sfy1vib0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="cnsy8cctb"/><path class="amaky3v5u"/><path class="mtzy7oq7x"/><path class="sa18abbmq"/><path class="r_4ceuibd"/><path class="sfy1vib0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:valhalla-maps" /></template>
