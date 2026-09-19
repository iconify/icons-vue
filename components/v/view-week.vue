<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt3t5jbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="xt3t5jbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:view-week" /></template>
