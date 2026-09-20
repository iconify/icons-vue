<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6rr5ss6f.css';
import '../../css/s/s222euk2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w6rr5ss6f"/><path class="s222euk2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nezha-dark" /></template>
