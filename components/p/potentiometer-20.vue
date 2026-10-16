<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9vkkfbyq.css';
import '../../css/u/uhh21oc6x.css';
import '../../css/d/d00rzfrbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l9vkkfbyq"/><path class="uhh21oc6x"/><path class="d00rzfrbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:potentiometer-20" /></template>
