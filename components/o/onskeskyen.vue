<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erd7kjaha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="erd7kjaha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:onskeskyen" /></template>
