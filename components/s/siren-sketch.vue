<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cgb4cpr-x.css';
import '../../css/o/o_ka54b_n.css';
import '../../css/x/xaz3ysbci.css';
import '../../css/f/fbow-u9gb.css';
import '../../css/x/xd-wgubdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cgb4cpr-x"/><path class="o_ka54b_n wm-k"/><path class="wm-k xaz3ysbci"/><path class="fbow-u9gb wm-a"/><path class="wm-s xd-wgubdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:siren-sketch" /></template>
