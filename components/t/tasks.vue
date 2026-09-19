<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9eg8jbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r9eg8jbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tasks" /></template>
