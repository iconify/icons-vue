<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eg_1hhaab.css';
import '../../css/h/hlt5i6brv.css';
import '../../css/k/k3zrs8bws.css';
import '../../css/e/ewealvn7e.css';
import '../../css/n/ngz-u36nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eg_1hhaab"/><path class="hlt5i6brv wm-k"/><path class="k3zrs8bws wm-a"/><path class="ewealvn7e wm-k"/><path class="ngz-u36nt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:toolbox-sketch" /></template>
