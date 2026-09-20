<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6_yb2boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c6_yb2boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mkvpriority-dark" /></template>
