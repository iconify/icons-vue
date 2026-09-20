<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czbxsikfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="czbxsikfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:octopus-deploy" /></template>
