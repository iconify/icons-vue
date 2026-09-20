<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpp_p0b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vpp_p0b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:paint-bucket-alt" /></template>
