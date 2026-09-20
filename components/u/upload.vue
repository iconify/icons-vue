<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5-g-233d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h5-g-233d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:upload" /></template>
