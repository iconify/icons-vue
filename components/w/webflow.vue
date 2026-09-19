<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igtflkirm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="igtflkirm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:webflow" /></template>
