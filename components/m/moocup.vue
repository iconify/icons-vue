<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpwap_bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xpwap_bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:moocup" /></template>
