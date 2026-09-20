<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2ei1uv_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e2ei1uv_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:social-security-administration-light" /></template>
