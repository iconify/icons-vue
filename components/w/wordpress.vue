<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkn-xcc_r.css';
import '../../css/n/nod8y87lz.css';
import '../../css/v/v3xj24_6m.css';
import '../../css/m/mwmj-lbpq.css';
import '../../css/f/fnvdoxl6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkn-xcc_r"/><path class="nod8y87lz"/><path class="v3xj24_6m"/><path class="mwmj-lbpq"/><path class="fnvdoxl6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:wordpress" /></template>
