<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kuybt0bap.css';
import '../../css/e/efd17ac1z.css';
import '../../css/w/wjnfdsdtm.css';
import '../../css/n/n5gs_1b0s.css';
import '../../css/d/d4jkpdbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kuybt0bap wm-k"/><path class="efd17ac1z wm-a"/><path class="wjnfdsdtm wm-k"/><path class="n5gs_1b0s wm-a"/><path class="d4jkpdbby wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:target-sketch" /></template>
