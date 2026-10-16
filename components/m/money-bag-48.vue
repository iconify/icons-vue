<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdt3zcvtz.css';
import '../../css/s/srn-1hkgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hdt3zcvtz"/><path class="srn-1hkgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:money-bag-48" /></template>
