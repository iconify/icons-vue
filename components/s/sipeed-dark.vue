<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghzt9mbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ghzt9mbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sipeed-dark" /></template>
