<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a3ij4ee4d.css';
import '../../css/x/x2xetcbew.css';
import '../../css/i/izb9cccdy.css';
import '../../css/j/jfru2eb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a3ij4ee4d wm-k"/><path class="wm-shadow x2xetcbew"/><path class="izb9cccdy wm-k"/><path class="jfru2eb2v wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:weight-engrave" /></template>
