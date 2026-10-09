<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqwmttb_b.css';
import '../../css/r/r_ehnoaxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wqwmttb_b"/><path class="r_ehnoaxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trending-down-48" /></template>
