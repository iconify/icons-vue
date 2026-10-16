<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqjo_17sw.css';
import '../../css/b/bxk-0nxsq.css';
import '../../css/w/wtv0jqdvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bqjo_17sw"/><path class="bxk-0nxsq"/><path class="wtv0jqdvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:recloser-20-bold" /></template>
