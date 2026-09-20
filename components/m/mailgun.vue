<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y412vxlxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y412vxlxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailgun" /></template>
