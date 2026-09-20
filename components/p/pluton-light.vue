<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbpngy_pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wbpngy_pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pluton-light" /></template>
