<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdro4pbns.css';
import '../../css/i/ixpob8bob.css';
import '../../css/e/e8807tbnq.css';
import '../../css/m/m0sdzlb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdro4pbns"/><circle r="0" class="ixpob8bob"><animate attributeName="r" begin=".67" calcMode="spline" dur="1.5s" keySplines="0.2 0.2 0.4 0.8;0.2 0.2 0.4 0.8;0.2 0.2 0.4 0.8" repeatCount="indefinite" values="0;1.75;0;0"/></circle><circle r="0" class="e8807tbnq"><animate attributeName="r" begin=".33" calcMode="spline" dur="1.5s" keySplines="0.2 0.2 0.4 0.8;0.2 0.2 0.4 0.8;0.2 0.2 0.4 0.8" repeatCount="indefinite" values="0;1.75;0;0"/></circle><circle r="0" class="m0sdzlb_u"><animate attributeName="r" begin="0" calcMode="spline" dur="1.5s" keySplines="0.2 0.2 0.4 0.8;0.2 0.2 0.4 0.8;0.2 0.2 0.4 0.8" repeatCount="indefinite" values="0;1.75;0;0"/></circle>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:typing" /></template>
