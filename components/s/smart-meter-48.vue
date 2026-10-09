<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw53-sbdu.css';
import '../../css/y/ymi4owbyw.css';
import '../../css/f/frfktfbcq.css';
import '../../css/z/zczeh0h7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lw53-sbdu"/><path class="ymi4owbyw"/><path class="frfktfbcq"/><path class="zczeh0h7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-meter-48" /></template>
