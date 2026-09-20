<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blkq5y2_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="blkq5y2_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:writefreely-dark" /></template>
