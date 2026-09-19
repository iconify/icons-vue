<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt-e5pb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rt-e5pb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:user-circle-fill-12" /></template>
