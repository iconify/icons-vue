<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_vsitbjn.css';
import '../../css/c/c_2_mxnve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o_vsitbjn"/><path class="c_2_mxnve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:volume-high" /></template>
