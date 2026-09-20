<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip3d1v6sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ip3d1v6sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:work-order-check-filled" /></template>
