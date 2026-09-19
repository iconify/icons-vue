<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6tkq1bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n6tkq1bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pause-circle" /></template>
