<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3trzrbdm.css';
import '../../css/l/lrflrndpo.css';
import '../../css/d/dm5bfnbry.css';
import '../../css/m/m_rznqb0n.css';
import '../../css/i/izcsuhbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e3trzrbdm"/><circle class="lrflrndpo"/><circle class="dm5bfnbry"/><circle class="m_rznqb0n"/><path class="izcsuhbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:speechbubble" /></template>
