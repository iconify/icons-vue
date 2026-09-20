<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_uqzkbxl.css';
import '../../css/d/dmbs_cc9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_uqzkbxl"/><path class="dmbs_cc9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:toshi" /></template>
