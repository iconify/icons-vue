<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k64ba8bom.css';
import '../../css/x/x5d5bbilf.css';
import '../../css/x/x77xoabnh.css';
import '../../css/y/yoxmr3_pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k64ba8bom"/><path class="x5d5bbilf"/><path class="x77xoabnh"/><path class="yoxmr3_pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:photodiode-20" /></template>
