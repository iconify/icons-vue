<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjnt2fbgz.css';
import '../../css/w/w8jjrpbxx.css';
import '../../css/h/h4pogicwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rjnt2fbgz"/><path class="w8jjrpbxx"/><path class="h4pogicwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:receipt-refund-20" /></template>
