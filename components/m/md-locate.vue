<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swlgwwb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="swlgwwb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-locate" /></template>
