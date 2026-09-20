<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8xu4hqsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":142.8,"height":35.2};
const content = `<path class="r8xu4hqsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:onelogin" /></template>
