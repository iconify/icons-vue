<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwgmdib_l.css';
import '../../css/o/opjlpfb1h.css';
import '../../css/s/s664m142x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pwgmdib_l"/><path class="opjlpfb1h"/><path class="s664m142x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pcb-20-bold" /></template>
