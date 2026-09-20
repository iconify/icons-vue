<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3k-tlztq.css';
import '../../css/m/mtnsy1o2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w3k-tlztq"/><path class="mtnsy1o2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mirotalk-light" /></template>
