<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhfn3yyhb.css';
import '../../css/o/of8os1b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mhfn3yyhb"/><path class="of8os1b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:owl-20" /></template>
