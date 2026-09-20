<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz0grn9tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dz0grn9tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:weblate-light" /></template>
