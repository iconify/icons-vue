<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/skb8opsgk.css';
import '../../css/q/qel8s913f.css';
import '../../css/f/fvxa0x2ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="skb8opsgk"/><path class="qel8s913f"/><path class="fvxa0x2ag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:router" /></template>
