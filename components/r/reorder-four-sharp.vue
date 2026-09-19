<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia11uwb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ia11uwb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:reorder-four-sharp" /></template>
