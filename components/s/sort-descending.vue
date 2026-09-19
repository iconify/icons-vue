<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmfj29_ra.css';
import '../../css/d/dv916pbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zmfj29_ra"/><path class="dv916pbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:sort-descending" /></template>
