<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k863ckb4g.css';
import '../../css/l/l5ybookek.css';
import '../../css/s/sqn_l5bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k863ckb4g"/><path class="l5ybookek"/><path class="sqn_l5bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-elbow-20" /></template>
