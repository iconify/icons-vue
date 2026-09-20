<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfwq3cbmt.css';
import '../../css/b/b8_9rtbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfwq3cbmt"/><path class="b8_9rtbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shields-io" /></template>
