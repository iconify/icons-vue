<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t00b9jt-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t00b9jt-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oneuptime-light" /></template>
