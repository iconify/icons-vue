<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/x2od90nbo.css';
import '../../css/w/wx677f5yg.css';
import '../../css/i/ipa4u5ria.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="x2od90nbo"/><path class="wx677f5yg"/><path class="ipa4u5ria"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sushi-01" /></template>
