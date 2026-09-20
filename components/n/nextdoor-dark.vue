<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9_q-5ksh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z9_q-5ksh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextdoor-dark" /></template>
