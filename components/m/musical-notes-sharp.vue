<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guw97hb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="guw97hb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:musical-notes-sharp" /></template>
