<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpletlpsy.css';
import '../../css/t/teyp2chse.css';
import '../../css/e/e29_vw92i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dpletlpsy"/><path class="teyp2chse"/><path class="e29_vw92i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:tether" /></template>
