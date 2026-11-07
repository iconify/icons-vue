<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp2190qyz.css';
import '../../css/x/x-pf1hz3a.css';
import '../../css/j/j020-w2mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp2190qyz"/><path class="x-pf1hz3a"/><path clip-rule="evenodd" class="j020-w2mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-warning-outline" /></template>
