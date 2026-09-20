<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmtm5li5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pmtm5li5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:marpui-light" /></template>
