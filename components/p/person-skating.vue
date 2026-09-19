<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qngno3bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="qngno3bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-skating" /></template>
