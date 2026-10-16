<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg5ptdx_f.css';
import '../../css/h/hclia1bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="qg5ptdx_f"/><path class="hclia1bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:yamtrack-dark" /></template>
