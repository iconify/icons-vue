<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5_g_9b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="g5_g_9b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:pharmacy" /></template>
