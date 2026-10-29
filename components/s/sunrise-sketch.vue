<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/buezohm7s.css';
import '../../css/f/fa586t8_z.css';
import '../../css/h/hsajntj5k.css';
import '../../css/v/vkn0j2bym.css';
import '../../css/h/hlzyut9fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="buezohm7s wm-k"/><path class="fa586t8_z wm-s"/><path class="hsajntj5k wm-k"/><path class="vkn0j2bym wm-a"/><path class="hlzyut9fw wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sunrise-sketch" /></template>
