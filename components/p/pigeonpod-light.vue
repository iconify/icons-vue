<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ico4pgh7p.css';
import '../../css/f/f-eqyxxaw.css';
import '../../css/a/au-64bc0v.css';
import '../../css/o/owqro5bmc.css';
import '../../css/m/mkh_ywbpr.css';
import '../../css/r/rlsef_w8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ico4pgh7p"/><path class="f-eqyxxaw"/><path class="au-64bc0v"/><path class="owqro5bmc"/><path class="mkh_ywbpr"/><path class="rlsef_w8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pigeonpod-light" /></template>
