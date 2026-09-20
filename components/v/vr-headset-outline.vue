<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv61dmbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xv61dmbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:vr-headset-outline" /></template>
