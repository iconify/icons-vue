<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs9nrxbwo.css';
import '../../css/i/ifixufl1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qs9nrxbwo"/><path class="ifixufl1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nginx" /></template>
