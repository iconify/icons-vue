<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nfod2ubxc.css';
import '../../css/b/bn62hcb1n.css';
import '../../css/s/sub_1cbow.css';
import '../../css/g/g7kvze86q.css';
import '../../css/t/tyl_u5bcc.css';
import '../../css/i/i7qv3i8gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nfod2ubxc wm-k"/><path class="bn62hcb1n wm-a"/><path class="sub_1cbow wm-shadow"/><path class="g7kvze86q wm-k"/><path class="tyl_u5bcc wm-a"/><path class="i7qv3i8gc wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:popcorn-engrave" /></template>
