<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh61nybyw.css';
import '../../css/r/rhmy8zb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fh61nybyw"/><path class="rhmy8zb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ovumcy-dark" /></template>
