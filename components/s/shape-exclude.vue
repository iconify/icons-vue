<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqcrtybxv.css';
import '../../css/w/wr6o5qbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qqcrtybxv"/><path class="wr6o5qbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:shape-exclude" /></template>
