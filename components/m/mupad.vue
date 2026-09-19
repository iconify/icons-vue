<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp_hivq3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":494,"height":512};
const content = `<path class="zp_hivq3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mupad" /></template>
