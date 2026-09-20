<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri3fh5btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ri3fh5btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sogo-dark" /></template>
