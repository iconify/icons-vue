<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6zrwub-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i6zrwub-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-musical-notes" /></template>
