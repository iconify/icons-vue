<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz-sn48ud.css';
import '../../css/o/omvzod--l.css';
import '../../css/c/c-6x-ib4z.css';
import '../../css/d/d-5gh6s9v.css';
import '../../css/d/dqysvab-v.css';
import '../../css/n/ngt_-acgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gz-sn48ud"/><path class="omvzod--l"/><path class="c-6x-ib4z"/><linearGradient id="SVGoWF1XdKd" x1="256" x2="256" y1="363.6" y2="514" gradientTransform="matrix(1 0 0 -1 0 514)" gradientUnits="userSpaceOnUse"><stop offset="0" class="d-5gh6s9v"/><stop offset="1" class="dqysvab-v"/></linearGradient><path fill="url(#SVGoWF1XdKd)" class="ngt_-acgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phpsysinfo" /></template>
