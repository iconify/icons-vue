<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/r/r2i0scb_x.css';
import '../../css/o/oymgzybxy.css';
import '../../css/l/l5ay6cc6w.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvIAeWcvK"><g class="ufeehvblu"><path class="r2i0scb_x"/><path class="oymgzybxy"/><path class="l5ay6cc6w"/></g></mask></defs><path mask="url(#SVGvIAeWcvK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:notebook-one" /></template>
