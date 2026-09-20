<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx10v2n2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sx10v2n2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tianji-dark" /></template>
