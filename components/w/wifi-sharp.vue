<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2nvqgbuj.css';
import '../../css/x/xadjgxb-b.css';
import '../../css/c/cni6_d2wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i2nvqgbuj"/><path class="xadjgxb-b"/><path class="cni6_d2wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:wifi-sharp" /></template>
