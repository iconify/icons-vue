<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lki3iqzto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lki3iqzto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openrouter-light" /></template>
