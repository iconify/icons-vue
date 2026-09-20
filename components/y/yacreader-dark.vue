<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf4-oobbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rf4-oobbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yacreader-dark" /></template>
