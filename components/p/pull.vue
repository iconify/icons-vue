<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1udlpbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":512};
const content = `<path class="m1udlpbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:pull" /></template>
