<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_7dyob4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k_7dyob4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sortifyr" /></template>
