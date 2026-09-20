<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q1c7blwuq.css';
import '../../css/k/kw2etuk8n.css';
import '../../css/p/pvfzuob1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="q1c7blwuq"/><circle class="kw2etuk8n"/><path class="pvfzuob1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ticket-3" /></template>
