<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lixhw-b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lixhw-b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mashable" /></template>
