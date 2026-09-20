<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz3z958ur.css';
import '../../css/u/utltrjg1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uz3z958ur"/><path class="utltrjg1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:manifest-light" /></template>
