<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtmq0gbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mtmq0gbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:order-edit-filled" /></template>
