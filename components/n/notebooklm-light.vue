<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7wwqbb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u7wwqbb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notebooklm-light" /></template>
