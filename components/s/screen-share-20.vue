<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqxty8b1p.css';
import '../../css/k/kvl9ucc0s.css';
import '../../css/p/p1_r36byr.css';
import '../../css/w/wx3unnb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bqxty8b1p"/><path class="kvl9ucc0s"/><path class="p1_r36byr"/><path class="wx3unnb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:screen-share-20" /></template>
