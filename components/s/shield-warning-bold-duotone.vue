<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoqk-f2dc.css';
import '../../css/l/lp2190qyz.css';
import '../../css/x/x-pf1hz3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoqk-f2dc"/><path class="lp2190qyz"/><path class="x-pf1hz3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-warning-bold-duotone" /></template>
