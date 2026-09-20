<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r59kf3bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="r59kf3bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:seatbelt" /></template>
