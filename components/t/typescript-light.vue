<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lddffrb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lddffrb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typescript-light" /></template>
