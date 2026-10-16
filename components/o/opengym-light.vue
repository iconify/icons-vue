<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2j7g4b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a2j7g4b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opengym-light" /></template>
