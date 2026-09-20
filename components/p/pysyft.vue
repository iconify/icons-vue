<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg6a0ckqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg6a0ckqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pysyft" /></template>
