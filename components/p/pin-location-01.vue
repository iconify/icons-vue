<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tcwe4ewrv.css';
import '../../css/c/cy50z2-cm.css';
import '../../css/e/e-zqnqb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="tcwe4ewrv"/><path class="cy50z2-cm"/><path class="e-zqnqb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pin-location-01" /></template>
