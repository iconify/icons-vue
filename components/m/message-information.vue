<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/p/p1njaob-i.css';
import '../../css/u/ulke3igkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="p1njaob-i"/><path class="ulke3igkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-information" /></template>
