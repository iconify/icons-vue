<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hiajun_0u.css';
import '../../css/y/y2-r41asb.css';
import '../../css/w/wbefhlbfs.css';
import '../../css/s/sdi9acbkd.css';
import '../../css/z/zu7t2wbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hiajun_0u wm-k"/><path class="wm-a y2-r41asb"/><path class="wbefhlbfs wm-shadow"/><path class="sdi9acbkd wm-k"/><path class="wm-a zu7t2wbxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:users-engrave" /></template>
