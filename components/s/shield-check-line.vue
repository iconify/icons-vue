<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsyhy6zme.css';
import '../../css/a/ag85robiu.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 xsyhy6zme"/><path class="ag85robiu clr-i-outline clr-i-outline-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:shield-check-line" /></template>
