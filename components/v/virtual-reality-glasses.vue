<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f35axhbvy.css';
import '../../css/q/q8yb-9b3a.css';
import '../../css/b/b9g5g3b6s.css';
import '../../css/s/s1-q6gzfb.css';
import '../../css/n/n61qrv7rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="f35axhbvy"/><path class="q8yb-9b3a"/><path class="b9g5g3b6s"/><path clip-rule="evenodd" class="s1-q6gzfb"/><path class="n61qrv7rb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:virtual-reality-glasses" /></template>
