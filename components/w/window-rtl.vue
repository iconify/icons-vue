<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl1gw9yva.css';
import '../../css/g/gk_snkblx.css';
import '../../css/i/ifc5sxbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sl1gw9yva"/><path class="gk_snkblx"/><circle class="ifc5sxbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:window-rtl" /></template>
