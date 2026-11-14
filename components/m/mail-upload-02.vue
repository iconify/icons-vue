<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bwna43bhr.css';
import '../../css/d/df-j23bjo.css';
import '../../css/o/olf65k9xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bwna43bhr"/><path class="df-j23bjo"/><path class="olf65k9xu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-upload-02" /></template>
