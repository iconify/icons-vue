<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqg81jbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qqg81jbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typetype-dark" /></template>
