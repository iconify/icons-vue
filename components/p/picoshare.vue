<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9yn4-b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j9yn4-b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:picoshare" /></template>
