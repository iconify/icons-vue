<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mevf1wekm.css';
import '../../css/i/ik-b2z0to.css';
import '../../css/l/l8ziygp-z.css';
import '../../css/a/ah9y98gxq.css';
import '../../css/d/dfx-lljpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mevf1wekm"/><path class="ik-b2z0to"/><path class="l8ziygp-z"/><path class="ah9y98gxq"/><path class="dfx-lljpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tornado-small-broken" /></template>
