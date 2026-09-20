<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iij3ykbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iij3ykbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netgoat-light" /></template>
