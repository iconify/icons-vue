<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_is46bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d_is46bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sound-off-filled" /></template>
