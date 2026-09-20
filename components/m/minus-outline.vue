<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn_gf0ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xn_gf0ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:minus-outline" /></template>
