<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx_bfl8jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lx_bfl8jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sidebar-simple-open-fill" /></template>
