<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2y0w75do.css';
import '../../css/c/cb_h66bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x2y0w75do"/><path class="cb_h66bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wigwam" /></template>
