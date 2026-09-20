<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbgi26j-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fbgi26j-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton" /></template>
