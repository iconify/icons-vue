<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz5st3bpk.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gfobeg0lq.css';
import '../../css/q/qs14mnbed.css';
import '../../css/e/eviyv_ucu.css';
import '../../css/o/o2zzmo-mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz5st3bpk secondary"/><g class="dt0cm9dhy primary"><path class="gfobeg0lq"/><path class="qs14mnbed"/><path class="eviyv_ucu"/><path class="o2zzmo-mf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sandwich-duo" /></template>
