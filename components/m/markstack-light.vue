<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0l9w0esz.css';
import '../../css/d/da7n23beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a0l9w0esz"/><path class="da7n23beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:markstack-light" /></template>
