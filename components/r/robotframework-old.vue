<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofs7f2bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ofs7f2bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:robotframework-old" /></template>
