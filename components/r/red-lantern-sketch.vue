<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f6346fozd.css';
import '../../css/a/atzm8bc8c.css';
import '../../css/e/embnm_8cc.css';
import '../../css/a/aumnm37ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f6346fozd"/><path class="atzm8bc8c wm-k"/><path class="embnm_8cc wm-k"/><path class="aumnm37ge wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:red-lantern-sketch" /></template>
