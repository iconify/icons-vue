<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u01ibdujt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u01ibdujt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:midjourney-dark" /></template>
