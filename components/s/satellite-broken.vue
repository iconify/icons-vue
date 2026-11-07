<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p82yzhump.css';
import '../../css/e/efyt3acxm.css';
import '../../css/l/l1vnaybdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p82yzhump"/><path class="efyt3acxm"/><path class="l1vnaybdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:satellite-broken" /></template>
