<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1vrwcaop.css';
import '../../css/b/bt9ybibdw.css';
import '../../css/h/h0_dwo2xe.css';
import '../../css/o/oi4pzjbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="l1vrwcaop"/><path class="bt9ybibdw"/><path class="h0_dwo2xe"/><path class="oi4pzjbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:oncology" /></template>
