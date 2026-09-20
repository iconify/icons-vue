<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyl85rbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xyl85rbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-powerpoint-2018-light" /></template>
