<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/habx2hflc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="habx2hflc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:more-menu" /></template>
