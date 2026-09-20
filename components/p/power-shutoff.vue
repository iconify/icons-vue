<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn-xrwb_q.css';
import '../../css/q/qzipmcc8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dn-xrwb_q"/><path class="qzipmcc8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:power-shutoff" /></template>
