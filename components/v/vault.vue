<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x24_4tbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="x24_4tbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:vault" /></template>
