<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duchhy63s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="duchhy63s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:part-of-circle-4" /></template>
