<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvt85_2nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvt85_2nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:text-align-justify" /></template>
