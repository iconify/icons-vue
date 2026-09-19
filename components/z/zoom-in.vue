<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_8q9z4vg.css';
import '../../css/o/oof_74yzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="x_8q9z4vg"/><path class="oof_74yzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:zoom-in" /></template>
