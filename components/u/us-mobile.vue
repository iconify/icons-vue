<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7cy_2mli.css';
import '../../css/m/m0rx_181p.css';
import '../../css/p/p1h-zgy2y.css';
import '../../css/v/vu-ogmxzq.css';
import '../../css/s/sl0bimztx.css';
import '../../css/k/kc_qveb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m7cy_2mli"/><path class="m0rx_181p"/><path class="p1h-zgy2y"/><path class="vu-ogmxzq"/><path class="sl0bimztx"/><path class="kc_qveb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:us-mobile" /></template>
