<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9cwzmv4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x9cwzmv4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pango-dark" /></template>
