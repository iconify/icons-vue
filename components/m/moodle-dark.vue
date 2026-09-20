<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw_wwlb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iw_wwlb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:moodle-dark" /></template>
