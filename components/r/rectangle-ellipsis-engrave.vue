<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/irdladc7r.css';
import '../../css/l/l6l1smxsb.css';
import '../../css/x/xw_me4vft.css';
import '../../css/g/g2qaiez3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="irdladc7r wm-k"/><path class="l6l1smxsb wm-shadow"/><path class="wm-k xw_me4vft"/><path class="g2qaiez3p wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rectangle-ellipsis-engrave" /></template>
