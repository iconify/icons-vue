<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzh9h3blb.css';
import '../../css/t/tpzq2ccev.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 zzh9h3blb"/><path class="clr-i-outline clr-i-outline-path-2 tpzq2ccev"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:replay-one-line" /></template>
