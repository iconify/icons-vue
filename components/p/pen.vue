<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn97v2brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hn97v2brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:pen" /></template>
