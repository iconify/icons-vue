<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow9_qhf_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ow9_qhf_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:weight-hanging" /></template>
