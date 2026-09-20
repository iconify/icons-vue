<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce_v1otid.css';
import '../../css/i/i_xqkgcuh.css';
import '../../css/t/tw_7s6b8r.css';
import '../../css/o/ofdw__inh.css';
import '../../css/j/j4jcajbfq.css';
import '../../css/s/scl2a1b5a.css';
import '../../css/j/ji3byv7qt.css';
import '../../css/j/jzx08jtvn.css';
import '../../css/o/oqljh9zsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<rect class="ce_v1otid"/><path class="i_xqkgcuh"/><path class="tw_7s6b8r"/><path class="ofdw__inh"/><circle class="j4jcajbfq"/><path class="scl2a1b5a"/><path class="ji3byv7qt"/><circle class="jzx08jtvn"/><path class="oqljh9zsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:mobile-info" /></template>
