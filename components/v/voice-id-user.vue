<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rc4xfv36q.css';
import '../../css/t/t5pka63op.css';
import '../../css/f/fnmgaj5ib.css';
import '../../css/s/sdm_mab_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rc4xfv36q"/><path class="t5pka63op"/><path class="fnmgaj5ib"/><path class="sdm_mab_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:voice-id-user" /></template>
