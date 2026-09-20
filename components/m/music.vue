<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si0c0nhwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="si0c0nhwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:music" /></template>
