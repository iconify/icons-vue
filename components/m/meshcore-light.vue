<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h227az4ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h227az4ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meshcore-light" /></template>
