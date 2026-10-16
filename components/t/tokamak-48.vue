<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as2_m7byb.css';
import '../../css/f/fe3vb5b8y.css';
import '../../css/j/j6ppqza5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="as2_m7byb"/><path class="fe3vb5b8y"/><path class="j6ppqza5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tokamak-48" /></template>
