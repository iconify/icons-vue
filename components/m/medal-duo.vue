<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2ch_2b_h.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/v7mrbtq2p.css';
import '../../css/n/nkgwb_xhr.css';
import '../../css/c/c2tnx8j5w.css';
import '../../css/y/yhe1qpqgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2ch_2b_h secondary"/><g class="dt0cm9dhy primary"><path class="v7mrbtq2p"/><path class="nkgwb_xhr"/><path class="c2tnx8j5w"/><path class="yhe1qpqgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:medal-duo" /></template>
