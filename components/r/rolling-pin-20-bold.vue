<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz2l3p02o.css';
import '../../css/t/tb-omd_8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gz2l3p02o"/><path class="tb-omd_8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rolling-pin-20-bold" /></template>
