<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uevutyekl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="uevutyekl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:vignette" /></template>
