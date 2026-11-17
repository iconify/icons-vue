<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyt5mjbab.css';
import '../../css/x/xr2-xybln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lyt5mjbab"/><path class="xr2-xybln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:solidcraft-light" /></template>
