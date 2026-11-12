<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwah2sb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jwah2sb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:relic-storage-dark" /></template>
