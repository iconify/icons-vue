<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_wks7bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d_wks7bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:shake" /></template>
