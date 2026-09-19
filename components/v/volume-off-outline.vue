<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m90aoem4n.css';
import '../../css/o/ojinh4u0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m90aoem4n"/><path class="ojinh4u0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:volume-off-outline" /></template>
