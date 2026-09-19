<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/i0wtp628f.css';
import '../../css/q/q7zvs2b6v.css';
import '../../css/d/d3tu5-t0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="i0wtp628f"/><circle class="q7zvs2b6v"/><path class="d3tu5-t0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:motorbike-02" /></template>
