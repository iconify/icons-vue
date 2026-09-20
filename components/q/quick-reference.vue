<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-gufo90d.css';
import '../../css/v/vvd0k01le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j-gufo90d"/><path class="vvd0k01le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quick-reference" /></template>
