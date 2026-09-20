<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3cvb4ysw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r3cvb4ysw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:qr-code-outline" /></template>
