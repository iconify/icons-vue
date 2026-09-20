<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrhf_hbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wrhf_hbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:toggle-warehouse-y-filled" /></template>
