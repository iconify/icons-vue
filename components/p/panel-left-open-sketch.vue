<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/phpr5f78c.css';
import '../../css/v/v7hhicl8z.css';
import '../../css/s/slj8phnoe.css';
import '../../css/x/xqz5s6pgz.css';
import '../../css/l/lyuu3snpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="phpr5f78c"/><path class="v7hhicl8z wm-k"/><path class="slj8phnoe wm-a"/><path class="wm-k xqz5s6pgz"/><path class="lyuu3snpg wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:panel-left-open-sketch" /></template>
