<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9aw4q0hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u9aw4q0hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:newshosting-light" /></template>
