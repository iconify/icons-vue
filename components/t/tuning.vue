<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsdqp2o5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gsdqp2o5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:tuning" /></template>
