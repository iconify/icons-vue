<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot0s3ib2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ot0s3ib2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:riven" /></template>
