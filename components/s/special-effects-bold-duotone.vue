<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg928d-qd.css';
import '../../css/l/lqupblb0q.css';
import '../../css/v/vx_l23zwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path class="lqupblb0q"/><path class="vx_l23zwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:special-effects-bold-duotone" /></template>
