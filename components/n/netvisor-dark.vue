<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pme45vd5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pme45vd5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netvisor-dark" /></template>
