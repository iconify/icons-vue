<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlj9kwion.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zlj9kwion"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:whisper-money" /></template>
