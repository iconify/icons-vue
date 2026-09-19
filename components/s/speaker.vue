<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/m/m3ok1mbxt.css';
import '../../css/t/t8_-p0a_v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGW8SYSbEt"><g class="ufeehvblu"><path class="m3ok1mbxt"/><path class="t8_-p0a_v"/></g></mask></defs><path mask="url(#SVGW8SYSbEt)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:speaker" /></template>
