<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu8psr46c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lu8psr46c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xfinity" /></template>
