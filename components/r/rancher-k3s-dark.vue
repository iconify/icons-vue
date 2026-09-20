<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1qg1ub9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a1qg1ub9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-k3s-dark" /></template>
