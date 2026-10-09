<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2wj_vbdg.css';
import '../../css/v/v0d4hxfqr.css';
import '../../css/c/coi900bro.css';
import '../../css/i/ilidubbxi.css';
import '../../css/u/ux60etw0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g2wj_vbdg"/><path class="v0d4hxfqr"/><path class="coi900bro"/><path class="ilidubbxi"/><path class="ux60etw0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tennis-20-bold" /></template>
