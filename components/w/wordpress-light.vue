<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxi5sdbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sxi5sdbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wordpress-light" /></template>
