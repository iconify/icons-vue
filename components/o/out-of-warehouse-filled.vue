<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_x39ac_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k_x39ac_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:out-of-warehouse-filled" /></template>
