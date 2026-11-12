<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0e7f5gtl.css';
import '../../css/w/wzq2d5gcq.css';
import '../../css/y/ygjyfvpzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j0e7f5gtl"/><path class="wzq2d5gcq"/><path class="ygjyfvpzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:steamgriddb-light" /></template>
