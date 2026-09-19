<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/d/dit-i1b5h.css';
import '../../css/t/t4rl3tajf.css';
import '../../css/o/olp1xoh0o.css';
import '../../css/s/sxj1f8jvb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlXDTzzsm"><g class="wwvp95byt"><path class="dit-i1b5h"/><path class="t4rl3tajf"/><path class="olp1xoh0o"/><path class="sxj1f8jvb"/></g></mask></defs><path mask="url(#SVGlXDTzzsm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:usb-micro-two" /></template>
