<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/inftpnbxr.css';
import '../../css/w/wh1_e-bqz.css';
import '../../css/s/styllzb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="inftpnbxr"/><path class="wh1_e-bqz"/><path class="styllzb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:plugin-jigsaw-puzzle" /></template>
