<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwc1l2bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gwc1l2bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plain-week-dark" /></template>
