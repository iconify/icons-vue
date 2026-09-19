<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lida862-d.css';
import '../../css/m/mktkafb5g.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7rL5W2Zc"><g class="ufeehvblu"><path class="lida862-d"/><path class="mktkafb5g"/></g></mask></defs><path mask="url(#SVG7rL5W2Zc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:map-two" /></template>
