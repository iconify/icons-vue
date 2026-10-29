<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y2_zxkp4k.css';
import '../../css/c/c8v5lsbrm.css';
import '../../css/r/rcuiyzbuv.css';
import '../../css/n/n-0j0abdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k y2_zxkp4k"/><path class="c8v5lsbrm wm-a"/><path class="rcuiyzbuv wm-k"/><path class="n-0j0abdq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:podcast-sketch" /></template>
