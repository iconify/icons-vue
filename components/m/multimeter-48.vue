<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/batmvgb8l.css';
import '../../css/m/mud9nbkvp.css';
import '../../css/n/nv6m4c8xt.css';
import '../../css/z/zczeh0h7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="batmvgb8l"/><path class="mud9nbkvp"/><path class="nv6m4c8xt"/><path class="zczeh0h7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:multimeter-48" /></template>
