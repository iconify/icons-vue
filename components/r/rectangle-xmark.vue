<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bza6e2esc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bza6e2esc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:rectangle-xmark" /></template>
