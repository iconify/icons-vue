<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm8ba9fcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rm8ba9fcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:roon-dark" /></template>
