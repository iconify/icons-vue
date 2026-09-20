<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb3z4vbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb3z4vbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:oracle" /></template>
