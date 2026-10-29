<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/i/ic7dicpil.css';
import '../../css/w/wr92o1bsm.css';
import '../../css/c/c21_rfw1c.css';
import '../../css/k/kbxro98gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ic7dicpil wm-deco"/><path class="wm-deco wr92o1bsm"/><path class="c21_rfw1c wm-k"/><path class="kbxro98gm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wallet-blueprint" /></template>
