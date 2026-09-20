<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yaasi6hps.css';
import '../../css/p/p85yxxb5a.css';
import '../../css/z/zwuptyfnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yaasi6hps"/><path class="p85yxxb5a"/><path class="zwuptyfnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:network-monitor-team-1" /></template>
