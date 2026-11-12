<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw__jkbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jw__jkbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:msgvault-light" /></template>
