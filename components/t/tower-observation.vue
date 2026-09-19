<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov1mv-sfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ov1mv-sfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tower-observation" /></template>
