<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch2o2yfcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch2o2yfcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:x-outline" /></template>
