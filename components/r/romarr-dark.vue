<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a15d_-uch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a15d_-uch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:romarr-dark" /></template>
