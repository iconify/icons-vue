<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is0p9ccdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="is0p9ccdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:siyuan-light" /></template>
