<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw_su3bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gw_su3bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:medal-1st" /></template>
