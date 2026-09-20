<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7-r17bww.css';
import '../../css/e/eyfhqgb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w7-r17bww"/><path class="eyfhqgb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tidyquest-dark" /></template>
