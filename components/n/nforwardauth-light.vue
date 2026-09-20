<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gae81t6qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gae81t6qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nforwardauth-light" /></template>
