<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpe0arbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zpe0arbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:moodist-dark" /></template>
