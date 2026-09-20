<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt70wbcjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xt70wbcjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wifi-above-outstretched-hand" /></template>
