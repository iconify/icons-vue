<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xod2vyb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xod2vyb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:maine" /></template>
