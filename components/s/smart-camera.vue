<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz__jd44x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz__jd44x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:smart-camera" /></template>
