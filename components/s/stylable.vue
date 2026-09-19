<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trt9y-blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":455,"height":512};
const content = `<path class="trt9y-blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:stylable" /></template>
