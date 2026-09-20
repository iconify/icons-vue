<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evcjawbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="evcjawbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:melody-auth" /></template>
