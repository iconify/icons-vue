<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpi9kab-u.css';
import '../../css/k/kpwcb-rgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wpi9kab-u"/><path class="kpwcb-rgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:wireless-disabled-16" /></template>
