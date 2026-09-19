<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqohm2nbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="uqohm2nbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:umbrella-beach" /></template>
