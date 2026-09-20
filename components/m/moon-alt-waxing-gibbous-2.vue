<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiaiahb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="eiaiahb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waxing-gibbous-2" /></template>
