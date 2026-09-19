<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/x_z3bwv4t.css';
import '../../css/w/wttawfb0l.css';
import '../../css/z/z5_656mud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="x_z3bwv4t"/><path class="wttawfb0l"/><path class="z5_656mud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tablet-connected-usb" /></template>
