<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt_u63bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jt_u63bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:orb-dark" /></template>
