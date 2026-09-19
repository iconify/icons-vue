<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxm34-kzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":460,"height":512};
const content = `<path class="vxm34-kzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:searchengin" /></template>
