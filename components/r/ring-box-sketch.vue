<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/ph0ds1bxc.css';
import '../../css/h/h319o6bql.css';
import '../../css/g/guhpm9q2w.css';
import '../../css/v/vluw42orm.css';
import '../../css/d/dzi4dkhcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ph0ds1bxc wm-k"/><path class="h319o6bql"/><path class="guhpm9q2w"/><circle class="vluw42orm wm-a"/><path class="dzi4dkhcm wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ring-box-sketch" /></template>
