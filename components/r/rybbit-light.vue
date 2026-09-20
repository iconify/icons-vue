<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or3w7ac_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="or3w7ac_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rybbit-light" /></template>
