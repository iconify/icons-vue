<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdr4ynbph.css';
import '../../css/y/y-mhm093y.css';
import '../../css/v/v286mkswn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="qdr4ynbph"/><path class="y-mhm093y"/><path class="v286mkswn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:usdc" /></template>
