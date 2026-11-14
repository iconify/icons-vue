<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kvy1v7yel.css';
import '../../css/g/gn3v4ubtn.css';
import '../../css/s/swxcbrbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kvy1v7yel"/><path class="gn3v4ubtn"/><path class="swxcbrbza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:start-up-02" /></template>
