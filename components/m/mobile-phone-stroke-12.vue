<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0tmkpb-w.css';
import '../../css/u/u_fqzdbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<rect class="g0tmkpb-w"/><path class="u_fqzdbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:mobile-phone-stroke-12" /></template>
