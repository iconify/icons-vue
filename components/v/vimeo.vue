<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neo39kk3j.css';
import '../../css/e/e5z8i_kna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="neo39kk3j"/><path class="e5z8i_kna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vimeo" /></template>
