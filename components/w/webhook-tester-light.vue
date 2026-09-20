<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmxx6rzfe.css';
import '../../css/o/o53elobcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dmxx6rzfe"/><path class="o53elobcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:webhook-tester-light" /></template>
