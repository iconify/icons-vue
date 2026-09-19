<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb865obzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="nb865obzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:n-6-square" /></template>
