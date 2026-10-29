<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/runpznbra.css';
import '../../css/b/bux8_gbvv.css';
import '../../css/g/ga7n45b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="runpznbra wm-k"/><path class="bux8_gbvv wm-k"/><path class="ga7n45b4t wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:table-of-contents-sketch" /></template>
