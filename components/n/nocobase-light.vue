<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmgrvwqic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vmgrvwqic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nocobase-light" /></template>
