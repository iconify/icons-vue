<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/i/iku0m3-pn.css';
import '../../css/l/l3i9u4z1o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDRwlpcAP"><g class="wwvp95byt"><path class="iku0m3-pn"/><path class="l3i9u4z1o"/></g></mask></defs><path mask="url(#SVGDRwlpcAP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:message-emoji" /></template>
