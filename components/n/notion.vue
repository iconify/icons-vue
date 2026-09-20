<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0_wgyb4o.css';
import '../../css/t/tpvreibwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":268};
const content = `<path class="m0_wgyb4o"/><path class="tpvreibwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:notion" /></template>
